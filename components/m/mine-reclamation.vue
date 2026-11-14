<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l88314bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mine-reclamation" /></template>
<style>
.l88314bwa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 10.204v6.181q6.359.175 9.105 3.365H2.145q2.746-3.19 9.105-3.365v-3.661q-5-.362-5-5.724q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 6.25q2.813 0 4.25 1.376V7q0-.071.013-.141q.014-.07.04-.136t.064-.126t.087-.111t.107-.094q.057-.041.122-.072q.064-.03.133-.047t.14-.022q.405-.836 1.044-1.56q1.713-1.941 4-1.941q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 2.434-1.319 4.361q-1.408 2.059-3.681 2.343");
}

</style>
