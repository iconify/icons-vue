<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2z1e_f9o"/><path class="nfjsi_b6n"/><path class="cn2waqbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-top-open-bold-duotone" /></template>
<style>
.cn2waqbvb {
  fill: currentColor;
  d: path("M8.51172 14.7814C8.19748 14.5117 8.16118 14.0381 8.43066 13.7237C8.70024 13.4095 9.17388 13.3733 9.48828 13.6427L12 15.795L14.5117 13.6427C14.8261 13.3733 15.2998 13.4095 15.5693 13.7237C15.8388 14.0381 15.8025 14.5118 15.4883 14.7814L12.4883 17.3526C12.2074 17.5934 11.7926 17.5934 11.5117 17.3526L8.51172 14.7814Z");
}

.nfjsi_b6n {
  fill: currentColor;
  d: path("M3.00586 9.00011C3.03348 6.36429 3.19757 4.14629 4.17187 3.17198C5.34345 2.00051 7.22888 2.00011 11 2.00011L13 2.00011C16.7711 2.00011 18.6565 2.00053 19.8281 3.17198C20.8024 4.14629 20.9665 6.36429 20.9941 9.00011L3.00586 9.00011Z");
}

.t2z1e_f9o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.1716 20.8284C5.34318 22 7.2288 22 11 22L13 22C16.7713 22 18.6569 22 19.8285 20.8284C21 19.6569 21 17.7712 21 14L21 10C21 9.91573 21.0001 9.0824 21.0001 9L3.00006 9C3.00005 9.0824 3.00003 9.91573 3.00003 10L3.00003 14C3.00003 17.7712 3.00003 19.6569 4.1716 20.8284Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
