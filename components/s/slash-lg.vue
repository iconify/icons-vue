<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj4eti7ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dj4eti7ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:slash-lg" /></template>
