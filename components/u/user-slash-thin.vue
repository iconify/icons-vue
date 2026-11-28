<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd7wst1lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bd7wst1lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-slash-thin" /></template>
