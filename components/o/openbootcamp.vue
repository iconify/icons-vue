<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycchbsbfz.css';
import '../../css/n/n0pg1wbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":70,"height":51};
const content = `<ellipse class="ycchbsbfz"/><path clip-rule="evenodd" class="n0pg1wbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openbootcamp" /></template>
