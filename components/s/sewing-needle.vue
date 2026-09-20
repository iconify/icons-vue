<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVG99s6MeIy" x1="64.696" x2="80.225" y1="22.736" y2="37.085" gradientUnits="userSpaceOnUse"><stop offset=".203" class="j_fno4aum"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVG99s6MeIy)" class="rr2xhzsnk"/><path class="bkypy201o"/><path class="wcfjtdb1v"/><linearGradient id="SVGDf4DT0uh" x1="102.242" x2="110.844" y1="103.896" y2="95.88" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="fmyrvjuei"/><stop offset=".838" class="fmyrvjuei"/></linearGradient><path fill="url(#SVGDf4DT0uh)" class="ljpn2ybnh"/><linearGradient id="SVG1XoKMerc" x1="85.924" x2="71.757" y1="65.384" y2="51.217" gradientUnits="userSpaceOnUse"><stop offset=".038" class="j_fno4aum"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVG1XoKMerc)" class="cwq0qebdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:sewing-needle" /></template>
<style>
.bkypy201o {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M121.221 6.225c-2.76-2.6-6.57-3.26-11.93-.15c-3.36 1.95-7.24 5.49-12.15 10.58c-8.17 8.49-74.33 82.43-91.03 101.72c-2.32 2.67-2.36 4.29-1.84 4.81s1.94.39 4.75-1.95c19.22-16.04 92.96-81.16 102.27-90.43c4.16-4.14 7.67-7.88 9.18-9.67c5.14-6.12 4.02-11.82.75-14.91m-24.37 29.86c-1.41 1.41-3.11 2.22-4.31 1.02s-1.03-3.34.38-4.75l17.78-17.78c1.41-1.41 3.55-1.58 4.75-.38s.59 2.7-.82 4.12z");
}

.cwq0qebdq {
  d: path("M113.137 50.724c0 13.25-10.394 21.341-19.565 28.481l-.473.367c-.78.609-1.607 1.238-2.462 1.889c-8.025 6.111-18.013 13.718-18.013 23.822c0 11.022 10.47 18.719 25.462 18.719c11.716 0 24.873-9.613 25.62-21.645c.15-2.42.049-3.909-.205-4.642c-.107-.309-.418-.394-.58.251c-.77 3.08-2.17 6.04-2.72 7.24c-3.623 7.88-12.193 13.796-22.115 13.796c-12.047 0-20.462-5.642-20.462-13.719c0-7.628 8.895-14.401 16.042-19.844c.87-.663 1.711-1.303 2.505-1.921l.472-.368c9.576-7.454 21.494-16.731 21.494-32.426c0-12.273-6.75-21.594-15.814-27.77l-3.583 3.582q.736.48 1.443.986c5.91 4.231 12.954 11.69 12.954 23.202");
}

.eimpsdbhq {
  stop-color: var(--svg-color--01579b, #01579b);
}

.fmyrvjuei {
  stop-color: var(--svg-color--2f7889, #2f7889);
}

.j_fno4aum {
  stop-color: var(--svg-color--0091ea, #0091ea);
}

.ljpn2ybnh {
  d: path("M117.951 12.915c-2.57-1.58-4.9-.9-7.36 1.53c0 0 .19-.1.48-.19c1.4-1.15 3.32-1.24 4.44-.12c1.2 1.2.53 2.77-.88 4.18l-17.78 17.77c-1.41 1.41-3.05 2.16-4.25.96s-1.03-3.34.38-4.75l.57-.57s-6.17 4.07-2.18 8.16c2.11 2.16 5.88.95 7.38-.6l18.99-19.51c1.51-1.54 2.79-5.27.21-6.86");
}

.rr2xhzsnk {
  d: path("M74.018 14.06c-14.307 0-28.104 6.209-28.104 20.08c0 8.181 5.324 10.903 8.501 11.529c.89.175 1.349.2 1.887.2c.975 0 2.213-.362 2.569-.615c.214-.151.13-.23-.062-.26c-.556-.085-1.762-.295-2.724-.65c-1.533-.564-5.81-2.3-5.81-10.204c0-6.957 6.219-15.08 23.743-15.08c8.41 0 17.52 2.773 24.722 7.476l3.583-3.583c-8.606-5.863-19.297-8.893-28.305-8.893");
}

.wcfjtdb1v {
  fill: var(--svg-color--b9e4ea, #b9e4ea);
  d: path("M100.151 17.785c5.55-5.91 9.5-9.56 12.82-11.06c6.17-2.78 9.13.42 8.85.11c-2.64-2.85-6.27-4.14-12.09-1c-3.45 1.86-7.26 5.27-12.59 10.82c-8.16 8.51-74.57 82.64-91.03 101.72c-2.31 2.68-2.49 4.44-1.66 4.88c16.74-19.14 87.63-96.88 95.7-105.47");
  opacity: var(--svg-opacity--0-75, 0.75);
}

</style>
