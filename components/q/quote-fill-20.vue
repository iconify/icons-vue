<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6tizl6dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n6tizl6dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:quote-fill-20" /></template>
