<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-prufbkf.css';
import '../../css/g/gsx2n78yf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 j-prufbkf"/><path class="clr-i-outline clr-i-outline-path-2 gsx2n78yf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:notification-line" /></template>
