<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4iliac4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="b4iliac4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:map" /></template>
