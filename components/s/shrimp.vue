<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww5e5e7-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ww5e5e7-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:shrimp" /></template>
