<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0v1czp6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q0v1czp6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:vim-insert-mode-16" /></template>
