<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki6msqb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki6msqb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wall-sconce-flat-variant" /></template>
