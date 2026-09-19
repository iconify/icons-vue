<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gblmqib0s.css';
import '../../css/c/cjq4bgbqk.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 gblmqib0s"/><path class="cjq4bgbqk clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:network-globe-line" /></template>
