<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydiwi1btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydiwi1btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mojangstudios" /></template>
