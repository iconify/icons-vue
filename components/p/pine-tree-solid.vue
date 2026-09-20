<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b__9bgb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b__9bgb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pine-tree-solid" /></template>
