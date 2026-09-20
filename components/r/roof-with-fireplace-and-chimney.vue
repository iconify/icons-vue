<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wslcj4bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wslcj4bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roof-with-fireplace-and-chimney" /></template>
