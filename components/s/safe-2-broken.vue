<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n6f1xybpw"/><path class="fmbpbptfg"/><path class="tw1vd4bor"/><path class="si_mtzbvj"/><path class="zgmsqobxk"/><path class="xfkav6bcs"/><path class="jnsl4jgmw"/><path class="suncmkbcq"/><path class="xdjqjik-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-2-broken" /></template>
<style>
.fmbpbptfg {
  d: path("M4.5 7V10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnsl4jgmw {
  d: path("M12.75 12C12.75 12.4142 12.4142 12.75 12 12.75C11.5858 12.75 11.25 12.4142 11.25 12C11.25 11.5858 11.5858 11.25 12 11.25C12.4142 11.25 12.75 11.5858 12.75 12Z");
}

.n6f1xybpw {
  d: path("M12 12V8");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

.suncmkbcq {
  d: path("M12 12L15.6775 13.5761");
}

.tw1vd4bor {
  d: path("M4.5 14V17");
}

.xdjqjik-w {
  d: path("M11.9999 12L8.32227 13.5761");
}

.xfkav6bcs {
  d: path("M10 8.53513C10.5883 8.19479 11.2714 8 12 8C14.2091 8 16 9.79086 16 12C16 14.2091 14.2091 16 12 16C9.79086 16 8 14.2091 8 12C8 11.6547 8.04375 11.3196 8.12602 11");
}

.zgmsqobxk {
  d: path("M12 5C8.70017 5 7.05025 5 6.02513 6.02513C5 7.05025 5 8.70017 5 12C5 15.2998 5 16.9497 6.02513 17.9749C7.05025 19 8.70017 19 12 19C15.2998 19 16.9497 19 17.9749 17.9749C19 16.9497 19 15.2998 19 12C19 8.70017 19 7.05025 17.9749 6.02513C17.2933 5.34351 16.3354 5.11511 14.8 5.03857");
}

</style>
