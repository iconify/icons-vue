<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqod4tuvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqod4tuvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-plus-corner-fill-round" /></template>
