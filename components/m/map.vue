<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1lv1ybfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j1lv1ybfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:map" /></template>
