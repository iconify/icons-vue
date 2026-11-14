<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inord5bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":82,"height":82,"top":0.727};
const content = `<path class="inord5bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:open-design" /></template>
