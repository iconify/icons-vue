<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b38rg11dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b38rg11dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:star-2-flat" /></template>
