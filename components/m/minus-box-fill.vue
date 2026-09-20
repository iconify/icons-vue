<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdbp7xbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="fdbp7xbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:minus-box-fill" /></template>
