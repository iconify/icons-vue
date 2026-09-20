<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js0ml5b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="js0ml5b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:peace" /></template>
