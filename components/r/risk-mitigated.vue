<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw0w268fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:risk-mitigated" /></template>
<style>
.lw0w268fb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.248 19H7.04q-.086 0-.172-.006q-.085-.005-.17-.016q-.086-.012-.17-.028q-.084-.017-.167-.039q-.083-.023-.164-.05q-.082-.028-.161-.061q-.079-.032-.157-.07q-.077-.038-.151-.081t-.146-.091q-.071-.048-.139-.1t-.133-.109t-.126-.117q-.06-.061-.117-.125q-.057-.065-.109-.133t-.1-.139t-.091-.146t-.081-.152t-.071-.156t-.06-.161q-.028-.081-.05-.164t-.039-.167t-.029-.169q-.011-.085-.016-.171t-.006-.172q0-.086.005-.171q.006-.086.017-.171t.028-.17t.039-.167t.049-.164t.061-.161q.032-.079.07-.156q.038-.078.081-.152l4.96-8.614q.086-.149.191-.286q.104-.137.226-.259t.258-.227t.286-.191t.308-.152t.326-.111q.166-.044.337-.067q.171-.022.343-.022t.343.022t.337.067t.326.111t.308.152t.286.191q.136.105.258.227t.226.259t.191.286l3.044 5.286M12 8.5v4m0 3h.01m5.99-1v7m-3-3l3 3l3-3");
}

</style>
