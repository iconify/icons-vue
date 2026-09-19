<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvem3hemn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":662};
const content = `<path class="mvem3hemn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:spa" /></template>
