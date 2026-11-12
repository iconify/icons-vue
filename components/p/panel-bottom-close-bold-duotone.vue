<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nq9rqn1zt"/><path class="wj_8rllsk"/><path class="na-mcbnwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-bottom-close-bold-duotone" /></template>
<style>
.na-mcbnwp {
  fill: currentColor;
  d: path("M15.5693 6.72854C15.8388 7.04298 15.8026 7.51658 15.4883 7.78616L12.4883 10.3574C12.2074 10.5981 11.7926 10.5981 11.5117 10.3574L8.51172 7.78616C8.19739 7.51658 8.16118 7.04298 8.43066 6.72854C8.70025 6.41419 9.17384 6.37796 9.48828 6.64749L12 8.79983L14.5117 6.64749C14.8262 6.37796 15.2997 6.41419 15.5693 6.72854Z");
}

.nq9rqn1zt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.8284 3.17163C18.6568 2.00006 16.7712 2.00006 13 2.00006L11 2.00006C7.22873 2.00006 5.34312 2.00006 4.17154 3.17163C2.99997 4.34321 2.99997 6.22882 2.99997 10.0001L2.99997 14.0001C2.99997 14.0843 2.99993 14.9177 2.99994 15.0001L20.9999 15.0001C21 14.9177 21 14.0843 21 14.0001L21 10.0001C21 6.22882 21 4.34321 19.8284 3.17163Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wj_8rllsk {
  fill: currentColor;
  d: path("M20.9941 15C20.9665 17.6359 20.8024 19.8538 19.8281 20.8281C18.6565 21.9997 16.7712 22 13 22L11 22C7.2288 22 5.34345 21.9997 4.17187 20.8281C3.19755 19.8538 3.03348 17.6359 3.00586 15L20.9941 15Z");
}

</style>
