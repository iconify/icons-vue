<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fykosbbrv.css';
import '../../css/s/svhq3i9zq.css';
import '../../css/g/gezk6lbtr.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 fykosbbrv"/><path class="clr-i-solid clr-i-solid-path-2 svhq3i9zq"/><path class="clr-i-solid clr-i-solid-path-3 gezk6lbtr"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:slider-solid" /></template>
