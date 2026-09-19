<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gef9zeb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gef9zeb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:resize-full-screen" /></template>
