<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byk5dy4fd.css';
import '../../css/b/b4d3mc68f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="byk5dy4fd"/><path class="b4d3mc68f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:passenger-plus" /></template>
