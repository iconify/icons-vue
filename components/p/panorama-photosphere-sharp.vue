<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r852e6b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:panorama-photosphere-sharp" /></template>
<style>
.r852e6b9u {
  fill: currentColor;
  d: path("M7.636 19.115q-1.974-1.232-3.097-3.334L2 14.735v-5.47L4.539 8.22q1.123-2.102 3.097-3.333t4.345-1.232t4.345 1.232t3.097 3.333L22 9.266v5.469l-2.577 1.046q-1.123 2.102-3.097 3.334t-4.345 1.231t-4.345-1.231m4.345.231q1.84 0 3.361-.828q1.521-.827 2.627-2.295q-1.417.37-2.924.573q-1.507.204-3.064.204t-3.065-.204t-2.924-.573q1.106 1.468 2.627 2.295q1.522.828 3.362.828m0-14.692q-1.84 0-3.362.828q-1.521.827-2.627 2.295q1.418-.37 2.924-.573Q10.423 7 11.981 7t3.064.204t2.924.573q-1.105-1.468-2.627-2.295q-1.52-.828-3.361-.828");
}

</style>
