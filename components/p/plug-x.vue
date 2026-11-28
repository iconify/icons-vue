<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnw4vskur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnw4vskur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:plug-x" /></template>
