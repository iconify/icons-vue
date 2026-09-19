<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8-vdibbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o8-vdibbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pictureframe" /></template>
