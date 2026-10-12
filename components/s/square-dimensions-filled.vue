<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnk2uvdxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wnk2uvdxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-dimensions-filled" /></template>
