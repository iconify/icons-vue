<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qep29e6oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qep29e6oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:repo-compact" /></template>
