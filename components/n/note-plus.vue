<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd6744_hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd6744_hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:note-plus" /></template>
