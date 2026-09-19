<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw9wxrrim.css';
import '../../css/j/jlz7a01mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fw9wxrrim"/><path class="jlz7a01mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sleuthspy" /></template>
