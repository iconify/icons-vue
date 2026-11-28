<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7gh058nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7gh058nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:plane-x" /></template>
