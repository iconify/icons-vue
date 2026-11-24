<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d49124bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d49124bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tree-pine-filled" /></template>
