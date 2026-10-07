TEMPO CERTO - XML ANDROID LIMPO

Estrutura:
app/src/main/res/layout/
  activity_main.xml
  activity_resultado.xml
  item_forecast.xml

app/src/main/res/drawable/
  backgrounds + weather illustrations

app/src/main/res/values/
  colors.xml
  dimens.xml
  strings.xml

Observações:
1. O XML original recebido era FIGML/Figma, não XML Android. Esta versão foi reconstruída como Android XML.
2. As imagens 3D do Figma tinham apenas imageHash no arquivo original; os hashes não contêm a imagem. Por isso foram usados vetores leves como substitutos.
3. Se você tiver as imagens originais, substitua weather_illustration.xml e weather_card_illustration.xml por PNG/WebP e mantenha os mesmos IDs/referências.
4. O botão usa MaterialButton; o projeto precisa ter Material Components/Material 3 disponível.
5. As fontes Sora e Outfit do Figma não foram presumidas como instaladas. Para reproduzir exatamente a tipografia, adicione os arquivos .ttf em res/font e troque fontFamily.
