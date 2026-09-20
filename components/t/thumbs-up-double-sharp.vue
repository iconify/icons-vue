<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng1l55bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thumbs-up-double-sharp" /></template>
<style>
.ng1l55bdm {
  fill: currentColor;
  d: path("m17.842 16.192l.85-1.978V8.98h-5.565l.383-2.046l-.802-.816L15.808 3l.942.962l-.52 3.615H22v2.308l-2.692 6.307zM2 20v-8.615h1.462V20zm3 0v-8.154l5.02-5.038l.96.961l-.518 3.616h5.846v2.327L13.596 20z");
}

</style>
