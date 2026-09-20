<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_6sc8w-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y_6sc8w-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:station-wagon-and-arrow-right-above-arrow-left" /></template>
