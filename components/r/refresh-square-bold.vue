<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cih8fbbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cih8fbbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:refresh-square-bold" /></template>
