<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pi5v_hbnc"/><path class="lc7adbbfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:suter" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lc7adbbfq {
  fill: var(--svg-color--a674ff, #a674ff);
  d: path("M17.293 8.97a.975.975 0 0 1 0 1.379l-3.463 3.466a.972.972 0 0 1-1.662-.689c0-.258.103-.506.285-.689l3.463-3.466a.97.97 0 0 1 1.377 0");
}

.pi5v_hbnc {
  fill: var(--svg-color--38276d, #38276d);
  d: path("M7.06 10.14a.975.975 0 0 1 0-1.378l5.471-5.477a.974.974 0 1 1 1.377 1.38l-5.47 5.475a.97.97 0 0 1-1.377 0m9.879 3.72a.975.975 0 0 1 0 1.379l-5.471 5.476a.975.975 0 1 1-1.377-1.379l5.47-5.476a.974.974 0 0 1 1.377 0M6.706 15.03a.976.976 0 0 1 0-1.379l3.462-3.466a.976.976 0 0 1 1.377 0a.976.976 0 0 1 0 1.378L8.084 15.03a.973.973 0 0 1-1.377 0");
}

</style>
