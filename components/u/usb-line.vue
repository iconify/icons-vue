<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhfb2prjq.css';
import '../../css/s/shnp36blz.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 fhfb2prjq"/><path class="clr-i-outline clr-i-outline-path-2 shnp36blz"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:usb-line" /></template>
