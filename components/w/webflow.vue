<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlma8nb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1080,"height":674};
const content = `<path clip-rule="evenodd" class="rlma8nb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:webflow" /></template>
