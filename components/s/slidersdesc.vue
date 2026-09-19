<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orsskjd0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="orsskjd0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:slidersdesc" /></template>
