<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_h7uab0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="k_h7uab0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:worktree-small" /></template>
