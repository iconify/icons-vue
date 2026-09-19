<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1faat60f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="e1faat60f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:recycle" /></template>
