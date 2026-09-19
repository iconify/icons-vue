<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2-04zs8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z2-04zs8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:out-of-bounds" /></template>
