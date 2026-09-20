<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj55x0s_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj55x0s_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pixabay" /></template>
