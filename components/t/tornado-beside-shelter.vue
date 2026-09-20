<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/extss2joy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="extss2joy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tornado-beside-shelter" /></template>
