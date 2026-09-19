<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf2__ccvr.css';
import '../../css/h/h1963unzg.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 kf2__ccvr"/><path class="clr-i-outline clr-i-outline-path-2 h1963unzg"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tools-line" /></template>
