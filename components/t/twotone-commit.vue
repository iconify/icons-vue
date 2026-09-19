<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_idwnbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-commit" /></template>
<style>
.l_idwnbzy {
  fill: currentColor;
  d: path("M16.9 11a5 5 0 0 0-9.8 0H2v2h5.1a5 5 0 0 0 9.8 0H22v-2zM12 15c-1.66 0-3-1.34-3-3s1.34-3 3-3s3 1.34 3 3s-1.34 3-3 3");
}

</style>
