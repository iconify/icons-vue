<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":254,"height":254};
const content = `<defs><radialGradient id="SVG6UFCFeCN" cx="41.406%" cy="42.708%" r="50%" fx="41.406%" fy="42.708%"><stop offset="0%" class="ohd8g-2kh"/><stop offset="100%" class="an0juuz8b"/></radialGradient><radialGradient id="SVGCgxlNyXP" cx="44.271%" cy="42.708%" r="50%" fx="44.271%" fy="42.708%"><stop offset="0%" class="ohd8g-2kh"/><stop offset="100%" class="an0juuz8b"/></radialGradient><linearGradient id="SVGdlWcUdVg" x1="50%" x2="50%" y1="100%" y2="0%"><stop offset="0%" class="l2_nu0b6b"/><stop offset="100%" class="u4vox7ijr"/></linearGradient><linearGradient id="SVGubS1kldG" x1="88.778%" x2="30.149%" y1="98.342%" y2="-8.68%"><stop offset="0%" class="uxtmbpbdc"/><stop offset="100%" class="h3sgj53hj"/></linearGradient></defs><path fill="url(#SVGdlWcUdVg)" class="svqcewk5c"/><path fill="url(#SVGubS1kldG)" transform="translate(45.79 47.098)" class="b7bv2mqgm"/><path fill="url(#SVG6UFCFeCN)" transform="translate(45.79 47.098)" class="cvcc6nbsb"/><path fill="url(#SVGCgxlNyXP)" transform="translate(45.79 47.098)" class="fdi-t1h4g"/><path class="o550xj4fy"/><path class="onv2vy6gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:memcached" /></template>
<style>
.an0juuz8b {
  stop-color: var(--svg-color--c83737, #c83737);
}

.b7bv2mqgm {
  d: path("M8.891.655C-3.562 79.583 2.953 153.48 2.953 153.48h38.928c-3.704-19.704-16.992-109.724-5.938-110.021c5.924.94 32.99 76.371 32.99 76.371s5.96-.742 11.958-.742s11.959.742 11.959.742s27.066-75.43 32.99-76.371c11.053.297-2.235 90.317-5.938 110.02h38.927s6.516-73.896-5.938-152.824H116.85C109.99.736 83.89 46.51 80.891 46.51S51.792.736 44.932.655z");
}

.cvcc6nbsb {
  d: path("M73.214 144.267a9.213 9.213 0 1 1-18.427 0a9.213 9.213 0 0 1 18.427 0");
}

.fdi-t1h4g {
  d: path("M106.995 144.267a9.213 9.213 0 1 1-18.426 0a9.213 9.213 0 0 1 18.426 0");
}

.h3sgj53hj {
  stop-color: var(--svg-color--2ea19e, #2ea19e);
}

.l2_nu0b6b {
  stop-color: var(--svg-color--574c4a, #574c4a);
}

.o550xj4fy {
  d: path("M196.846 50.362c5.618 38.026 6.936 74.52 6.833 101.705c-.106 27.806-1.699 45.871-1.699 45.871h-32.767l-3.521 2.64h38.927s6.516-73.897-5.938-152.825zm-103.154-.96c10.226 11.376 27.913 41.567 30.35 41.567c-6.484-8.292-22.411-34.748-30.35-41.567M79.094 87.918c-11.054.297 2.234 90.317 5.938 110.02H51.05l-2.307 2.64h38.928c-3.685-19.604-16.856-108.825-6.103-110.021c-1.002-1.504-1.866-2.543-2.474-2.64m89.896 0c-5.923.94-32.99 76.371-32.99 76.371s-5.96-.742-11.958-.742c-3.549 0-6.604.218-8.67.41l-.65 2.971s5.961-.742 11.96-.742c5.997 0 11.958.742 11.958.742s26.862-74.936 32.907-76.371c-.651-1.65-1.456-2.61-2.557-2.64");
  opacity: var(--svg-opacity--0-1, 0.1);
}

.ohd8g-2kh {
  stop-color: var(--svg-color--db7c7c, #db7c7c);
}

.onv2vy6gv {
  fill: var(--svg-color--fff, #fff);
  d: path("M54.681 47.753c-12.453 78.928-5.938 152.825-5.938 152.825L51.035 198c-1.173-17.434-4.306-80.48 6.285-147.609h36.042c.763.01 1.787.635 2.969 1.65c-2.36-2.626-4.322-4.274-5.609-4.29zm107.959 0c-6.86.081-32.96 45.856-35.959 45.856c1.223 1.564 2.216 2.639 2.64 2.639c2.998 0 29.098-45.775 35.958-45.856h31.806l1.596-2.64zM84.207 93.196c8.755 13.148 30.515 73.732 30.515 73.732l.637-2.954c-5.372-14.732-25.844-69.961-30.987-70.778c-.056.002-.11-.006-.165 0m90.062 0c5.872 14.977-5.244 89.649-8.577 107.382l3.53-2.757c4.508-26.446 15.363-104.347 5.047-104.625");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.svqcewk5c {
  d: path("M0 171.19V82.17C0 10.271 10.26 0 82.086 0h89.189C243.1 0 253.36 10.271 253.36 82.171v89.019c0 71.9-10.26 82.17-82.086 82.17H82.086C10.261 253.36 0 243.09 0 171.19");
}

.u4vox7ijr {
  stop-color: var(--svg-color--80716d, #80716d);
}

.uxtmbpbdc {
  stop-color: var(--svg-color--268d83, #268d83);
}

</style>
