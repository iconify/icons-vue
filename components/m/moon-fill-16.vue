<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlel97gzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zlel97gzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:moon-fill-16" /></template>
