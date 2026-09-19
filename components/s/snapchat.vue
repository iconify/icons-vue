<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkwgj9bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bkwgj9bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:snapchat" /></template>
