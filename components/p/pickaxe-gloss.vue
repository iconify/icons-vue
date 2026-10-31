<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bix-405kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bix-405kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pickaxe-gloss" /></template>
