<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua60ycxbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua60ycxbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:paperclip" /></template>
