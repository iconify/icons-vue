<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig-sq8kjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":832};
const content = `<path class="ig-sq8kjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:webhostinghub" /></template>
