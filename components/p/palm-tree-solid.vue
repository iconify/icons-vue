<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bti7alb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bti7alb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:palm-tree-solid" /></template>
