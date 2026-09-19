<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3gt3fbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3gt3fbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:terminal-square-filled" /></template>
