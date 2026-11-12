<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rsrhfac5n"/><path class="xy8vo0b-r"/><path class="xr6hxtsid"/><path class="axlwdg30m"/><path class="zocpetdxz"/><path class="x4x8t_s-n"/><path class="yzgz32bhq"/><path class="bari53b2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-off-line-duotone" /></template>
<style>
.axlwdg30m {
  d: path("M16.7617 10.7051C17.4418 11.1352 18.0826 11.6651 18.666 12.2949");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.bari53b2u {
  d: path("M22 2L18.2219 5.77811L14.3625 9.63753L2 22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.x4x8t_s-n {
  d: path("M20.3213 7.14551C20.9083 7.60771 21.4698 8.12479 21.9997 8.69674");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xr6hxtsid {
  d: path("M5.33301 12.295C7.78006 9.65377 11.2376 8.76794 14.3625 9.63754");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xy8vo0b-r {
  d: path("M12.959 14.5083C13.8293 14.7024 14.6585 15.164 15.3339 15.8929");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yzgz32bhq {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zocpetdxz {
  d: path("M2 8.69694C6.38843 3.96024 12.9434 2.98729 18.2219 5.77811");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
