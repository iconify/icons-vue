<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t_jo1abzk"/><path class="i8b10zb5o"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:refill-pouch" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8b10zb5o {
  d: path("M10.25 3.5h.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 8.5 5.75v-.5a1.75 1.75 0 0 1 1.75-1.75m10.5 15A2.75 2.75 0 1 1 18 15.75");
}

.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

.t_jo1abzk {
  d: path("M12.675 20H6.459q-.139 0-.277-.015t-.273-.043q-.136-.03-.268-.073t-.258-.1t-.247-.127t-.232-.152t-.214-.176t-.195-.197t-.172-.217q-.081-.113-.149-.234t-.124-.248t-.096-.26q-.042-.132-.069-.268t-.04-.274t-.01-.277q.001-.139.018-.277l.87-7.25q.014-.118.039-.235t.06-.23t.081-.224t.101-.216t.12-.205t.138-.194t.154-.181t.171-.166t.185-.149q.096-.071.198-.133q.102-.061.209-.114q.107-.052.218-.094q.112-.042.227-.074q.114-.032.231-.054t.236-.032q.119-.011.238-.011h6.342q.119 0 .238.011q.118.011.236.032t.231.054q.115.032.227.074q.111.042.218.094q.107.053.209.114t.198.133q.096.07.185.149t.171.166t.154.181q.074.094.138.194t.12.205q.056.106.101.216t.081.224t.06.23q.025.117.039.235l.223 1.861");
}

</style>
