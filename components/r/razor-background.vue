<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vkpk8-1me"/><path class="y2_7kp8hr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:razor-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vkpk8-1me {
  fill: var(--svg-color--4fa8ff, #4fa8ff);
  d: path("M24 0H0v24h24z");
}

.y2_7kp8hr {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.268 9.334a.71.71 0 0 0-.727.698v3.95c.005.382.34.687.737.683a.71.71 0 0 0 .717-.684v-3.949a.71.71 0 0 0-.727-.698m-2.422-1.937c-.403 0-.727.31-.727.688v7.811c-.01.383.31.698.712.707c.398.01.732-.29.742-.673V8.085c0-.378-.325-.688-.727-.688m-2.423-3.392c-.403 0-.727.305-.727.688v14.619c0 .378.324.683.727.683s.726-.305.726-.683V4.692c0-.382-.324-.687-.726-.687M12 7.881c-.402 0-.727.296-.727.664v6.425c0 .364.325.664.727.664s.727-.295.727-.664V8.545c0-.368-.325-.664-.727-.664M9.577 4.005c-.402 0-.726.305-.726.683v14.629c0 .378.324.683.726.683c.403 0 .727-.305.727-.683V4.683c0-.378-.324-.678-.727-.683zM7.155 6.428c-.403 0-.727.3-.727.669v9.807c0 .369.324.669.727.669s.726-.3.726-.669V7.097c0-.368-.324-.669-.726-.669M4.732 9.334c-.402 0-.727.3-.727.67V14c0 .363.325.664.727.664s.727-.3.727-.664v-3.998c0-.368-.325-.669-.727-.669");
}

</style>
