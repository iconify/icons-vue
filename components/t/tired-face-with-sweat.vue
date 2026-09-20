<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmisexm3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qmisexm3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face-with-sweat" /></template>
