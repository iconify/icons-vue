<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6vl68bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y6vl68bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pickaxe-filled" /></template>
