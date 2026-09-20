<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhm9gv9uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lhm9gv9uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tag-text" /></template>
