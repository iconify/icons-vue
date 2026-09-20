<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7pq-zbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l7pq-zbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:mdsvex" /></template>
