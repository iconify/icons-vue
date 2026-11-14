<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqnq66wob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:video-180" /></template>
<style>
.kqnq66wob {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.665 3.829q-8.665 4.332-17.33 0Q3.177 3.75 3 3.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v15q0 .177.079.335q.067.134.18.232q.112.097.254.145q.141.047.29.036q.149-.01.282-.077q8.665-4.332 17.33 0q.158.079.335.079q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-15q0-.177-.079-.335q-.067-.134-.18-.232q-.112-.097-.254-.145q-.141-.047-.29-.036q-.149.01-.282.077m-8.158 6.086l.329.165q1.186.593 1.186 1.92t-1.186 1.921l-.329.164q-1.123.562-2.19-.098q-1.067-.659-1.067-1.914v-.146q0-1.255 1.067-1.914q1.067-.66 2.189-.099z");
}

</style>
