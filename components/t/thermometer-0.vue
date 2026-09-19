<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt8qg7b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1792};
const content = `<path class="jt8qg7b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:thermometer-0" /></template>
