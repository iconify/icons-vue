<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daw47cb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="daw47cb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thumbnail-2" /></template>
