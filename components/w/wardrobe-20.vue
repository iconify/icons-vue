<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj594fbcf.css';
import '../../css/a/avqgz5tna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jj594fbcf"/><path class="avqgz5tna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wardrobe-20" /></template>
