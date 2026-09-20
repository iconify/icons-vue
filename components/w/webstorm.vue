<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGYCB4I0lC" x1="43.896%" x2="66.16%" y1="1.951%" y2="95.244%"><stop offset="28%" class="xtrtznbzt"/><stop offset="94%" class="r_lf9ybqi"/></linearGradient><linearGradient id="SVGGyvlDdgG" x1="33.063%" x2="70.362%" y1="15.078%" y2="84.685%"><stop offset="14%" class="bzg--8baj"/><stop offset="37%" class="xtrtznbzt"/></linearGradient><linearGradient id="SVGTkdXRckd" x1="44.416%" x2="56.203%" y1="25.058%" y2="90.203%"><stop offset="28%" class="xtrtznbzt"/><stop offset="94%" class="r_lf9ybqi"/></linearGradient></defs><path fill="url(#SVGYCB4I0lC)" class="iwui5w2ct"/><path fill="url(#SVGGyvlDdgG)" class="o3xjyl5sq"/><path fill="url(#SVGTkdXRckd)" class="cxuevjphi"/><path class="wj8kk3bmp"/><path class="at4v6hb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:webstorm" /></template>
<style>
.at4v6hb1y {
  fill: var(--svg-color--fff, #fff);
  d: path("M67.947 177.76h60v10h-60zm56.8-109.84l-8.934 35.013L105.6 67.92H95.44L85.2 102.933L76.293 67.92h-14l17.147 60.027h11.253l9.814-34.747l9.706 34.747H121.6l17.12-60.027zm16.48 51.707l7.813-9.6a27.57 27.57 0 0 0 17.973 7.306c5.334 0 8.694-2.133 8.694-5.68v-.16c0-1.899-.665-3.27-3.058-4.57l-.382-.2l-.41-.198l-.216-.1l-.454-.198l-.238-.1l-.5-.198l-.531-.2l-.278-.1l-.58-.2l-.303-.102l-.63-.204l-.667-.206l-.347-.104l-.72-.21l-.758-.214l-.795-.216l-.835-.221l-1.605-.416l-1.144-.307l-.748-.207l-.734-.21l-.72-.215l-.707-.217l-.694-.222l-.68-.227l-.334-.115l-.658-.235l-.643-.241l-.629-.248l-.614-.255l-.301-.13l-.591-.267l-.576-.275c-5.582-2.748-8.889-6.796-8.998-14.338l-.002-.574c0-10.792 8.59-17.98 20.68-18.13l.386-.003a34.67 34.67 0 0 1 22.347 7.653l-6.88 9.974a28.1 28.1 0 0 0-15.653-5.92c-5.067 0-7.734 2.32-7.734 5.333v.187c0 2.402.988 3.856 4.09 5.227l.456.196q.237.098.487.194l.518.195l.548.196l.58.196l.611.199l.646.2l.679.203l1.083.312l.767.213l.803.217l1.719.452q.426.112.843.225l.826.23q.205.057.407.116l.8.236l.781.242l.765.247l.746.252l.728.26l.357.131l.7.27c7.724 3.045 12.013 7.432 12.138 15.507l.002.524c0 11.946-9.12 18.667-22.106 18.667a38.24 38.24 0 0 1-25.52-9.627");
}

.bzg--8baj {
  stop-color: var(--svg-color--fcf84a, #fcf84a);
}

.cxuevjphi {
  d: path("m204.72 74.533l23.28 41.36l28-29.2l-20.56-50.826z");
}

.iwui5w2ct {
  d: path("M34.507 231.36L0 26.827L63.813.347L104.56 24.56l37.333-20.133l77.787 29.866L176.053 256z");
}

.o3xjyl5sq {
  d: path("m256 86.693l-33.04-81.6L163.013 0L70.48 88.907l24.907 114.586l46.506 32.614L256 168.4l-28-52.507z");
}

.r_lf9ybqi {
  stop-color: var(--svg-color--087cfa, #087cfa);
}

.wj8kk3bmp {
  d: path("M48 48h160v160H48z");
}

.xtrtznbzt {
  stop-color: var(--svg-color--07c3f2, #07c3f2);
}

</style>
