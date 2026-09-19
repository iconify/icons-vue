<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5mn0ab7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="e5mn0ab7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:wpexplorer" /></template>
