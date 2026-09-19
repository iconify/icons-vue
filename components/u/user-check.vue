<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjrmon3sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjrmon3sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-check" /></template>
