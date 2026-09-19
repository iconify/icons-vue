<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="yql563b6n"/><path class="ed6aqk8ey"/><path class="u-255abjh"/><path class="cbstye3uw"/><path class="r03e_db_e"/><path class="b_wj-kbvr"/><path class="zyxuxxbwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photo-studio-pro" /></template>
<style>
.b_wj-kbvr {
  d: path("m28.183 24.025l-.91 2.577c-1.118 3.165-6.601 8.338-12.741 7.383m5.285-10.01l.91-2.577c1.118-3.165 6.601-8.338 12.741-7.383");
}

.cbstye3uw {
  d: path("m25.317 20.03l2.17 1.662c2.664 2.04 5.89 8.854 3.084 14.398m-7.888-8.12l-2.17-1.662c-2.664-2.04-5.89-8.854-3.084-14.398");
}

.ed6aqk8ey {
  d: path("m20.631 21.521l2.251-1.55c2.765-1.903 10.24-2.866 14.647 1.516m-10.16 4.992l-2.251 1.55c-2.765 1.903-10.24 2.866-14.647-1.516");
}

.r03e_db_e {
  d: path("m27.399 21.562l.778 2.62c.956 3.217-.439 10.625-5.968 13.462m-1.608-11.206l-.778-2.62c-.956-3.217.439-10.625 5.968-13.462");
}

.u-255abjh {
  d: path("m22.732 20.014l2.732.07c3.355.085 9.97 3.7 10.958 9.835m-11.154-1.933l-2.732-.07c-3.355-.085-9.97-3.7-10.958-9.835");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yql563b6n {
  d: path("M37.769 24c0 7.604-6.165 13.769-13.769 13.769S10.231 31.604 10.231 24S16.396 10.231 24 10.231S37.769 16.396 37.769 24");
}

.zyxuxxbwx {
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
