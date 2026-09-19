<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7h7oigqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7h7oigqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:soccer-ball" /></template>
