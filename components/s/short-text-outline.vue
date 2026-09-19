<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fat_nsbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fat_nsbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:short-text-outline" /></template>
