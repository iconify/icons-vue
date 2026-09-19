<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1lw2cc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="b1lw2cc6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:subscript" /></template>
