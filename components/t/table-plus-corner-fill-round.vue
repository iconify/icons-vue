<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fns7kab-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fns7kab-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-plus-corner-fill-round" /></template>
