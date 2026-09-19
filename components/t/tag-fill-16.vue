<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iminszb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iminszb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tag-fill-16" /></template>
