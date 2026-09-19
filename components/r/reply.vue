<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bha938boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bha938boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:reply" /></template>
