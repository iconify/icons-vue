<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl0y2rbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gl0y2rbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:text-indent-left" /></template>
