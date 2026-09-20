<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw6_8x8qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kw6_8x8qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wav-16" /></template>
