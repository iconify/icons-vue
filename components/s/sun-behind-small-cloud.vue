<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w8idfru1h"/><circle class="nyg1cc8-h"/><path class="aiyfz8a7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:sun-behind-small-cloud" /></template>
<style>
.aiyfz8a7l {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M29.777 23.2c-.642 0-1.26.1-1.843.285c-.688-2.028-2.56-3.485-4.767-3.485c-2.368 0-4.35 1.678-4.899 3.937a3.4 3.4 0 0 0-2.101-.736c-1.933 0-3.5 1.611-3.5 3.6c0 .483.096.941.264 1.363A3.7 3.7 0 0 0 11.889 28C9.741 28 8 29.791 8 32s1.741 4 3.889 4h17.889C33.214 36 36 33.136 36 29.6c0-3.535-2.786-6.4-6.223-6.4");
}

.nyg1cc8-h {
  cx: 18px;
  cy: 18px;
  r: 10px;
  fill: var(--svg-color--ffac33, #ffac33);
}

.w8idfru1h {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M16 2s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2zm18 14s2 0 2 2s-2 2-2 2h-2s-2 0-2-2s2-2 2-2zM4 16s2 0 2 2s-2 2-2 2H2s-2 0-2-2s2-2 2-2zm5.121-8.707s1.414 1.414 0 2.828s-2.828 0-2.828 0L4.878 8.708s-1.414-1.414 0-2.829c1.415-1.414 2.829 0 2.829 0zm20.587 2.828s-1.414 1.414-2.828 0s0-2.828 0-2.828l1.414-1.414s1.414-1.414 2.828 0s0 2.828 0 2.828zm-21 21s-1.414 1.414-2.828 0s0-2.828 0-2.828l1.414-1.414s1.414-1.414 2.828 0s0 2.828 0 2.828z");
}

</style>
