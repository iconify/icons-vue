<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwkkckaky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wwkkckaky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:spinner-2" /></template>
