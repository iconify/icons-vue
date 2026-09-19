<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5f5ksbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p5f5ksbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelwand" /></template>
