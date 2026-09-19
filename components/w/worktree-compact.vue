<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7kzhix4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a7kzhix4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:worktree-compact" /></template>
