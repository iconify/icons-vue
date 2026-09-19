<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1-c0l79h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1-c0l79h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tree-filled" /></template>
