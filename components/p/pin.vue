<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx51n-rzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lx51n-rzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:pin" /></template>
