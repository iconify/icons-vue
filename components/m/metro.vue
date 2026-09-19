<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="phm49tbyx"/><path class="lqmms-grf"/><path class="onnajhi9p"/><path class="r-yssfbyh"/><path class="pstqdj_6m"/><path class="mui8s_bkc"/><path class="b0ssc5b1x"/><g class="n1mjunbsu"><circle class="g5z-fub4w"/><circle class="u4-rqntim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:metro" /></template>
<style>
.b0ssc5b1x {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M47.2 40.5c0 1.1-.9 1.9-2 1.9h-4.7c-1.1 0-2-.9-2-1.9c0-1.1.9-1.9 2-1.9h4.7c1.2 0 2 .9 2 1.9m-30.4 0c0-1.1.9-1.9 2-1.9h4.7c1.1 0 2 .9 2 1.9c0 1.1-.9 1.9-2 1.9h-4.7c-1.2.1-2-.8-2-1.9m30.4-10.1c0 1.5-1.2 2.7-2.7 2.7h-25c-1.5 0-2.7-1.2-2.7-2.7v-8.6c0-1.5 1.2-2.7 2.7-2.7h25.1c1.5 0 2.7 1.2 2.7 2.7v8.6z");
}

.g5z-fub4w {
  cx: 21.1px;
  cy: 40.5px;
  r: 1.7px;
}

.lqmms-grf {
  fill: var(--svg-color--94989b, #94989b);
  d: path("m20.2 46.3l-6.5 9.4c.8.6 1.7 1.2 2.5 1.8l7.3-11.1c0-.1-3.3-.1-3.3-.1");
}

.mui8s_bkc {
  fill: var(--svg-color--c7e755, #c7e755);
  d: path("M49.3 44.2c0 1.8-1.4 3.2-3.2 3.2H17.9c-1.8 0-3.2-1.4-3.2-3.2V20.7c0-12.6 34.5-12.6 34.5 0z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.onnajhi9p {
  fill: var(--svg-color--e6e6e6, #e6e6e6);
  d: path("M20.2 46.3h-3.3l-5.6 7.3c.8.7 1.5 1.4 2.4 2z");
}

.phm49tbyx {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.pstqdj_6m {
  fill: var(--svg-color--e6e6e6, #e6e6e6);
  d: path("m43.8 46.3l6.5 9.4c.8-.6 1.6-1.3 2.4-2l-5.6-7.3h-3.3z");
}

.r-yssfbyh {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M43.8 46.3h-3.3l7.3 11.1c.9-.5 1.7-1.1 2.5-1.8z");
}

.u4-rqntim {
  cx: 42.9px;
  cy: 40.5px;
  r: 1.7px;
}

</style>
