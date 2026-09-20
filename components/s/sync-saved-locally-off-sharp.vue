<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp_x1zb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sync-saved-locally-off-sharp" /></template>
<style>
.kp_x1zb_g {
  fill: currentColor;
  d: path("m21.192 22.608l-3.146-3.146H1.77v-1h15.272l-1-1H3V5.042h.615L1.392 2.808L2.1 2.1l19.8 19.8zM21 17.273h-.877L13.79 10.94l2.099-2.078l-.714-.714l-2.079 2.079l-5.784-5.765H21z");
}

</style>
