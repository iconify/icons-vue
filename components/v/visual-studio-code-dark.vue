<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4wxfh01e.css';
import '../../css/n/ni-dbjlax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j4wxfh01e"/><path class="ni-dbjlax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:visual-studio-code-dark" /></template>
