<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr4e3jb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr4e3jb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:trello" /></template>
