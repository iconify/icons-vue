<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k97abjb9v.css';
import '../../css/g/gtbcxr-sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k97abjb9v"/><path class="gtbcxr-sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pine-tree-20-bold" /></template>
