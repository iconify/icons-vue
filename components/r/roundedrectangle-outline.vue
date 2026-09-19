<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb1nv6bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="jb1nv6bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:roundedrectangle-outline" /></template>
