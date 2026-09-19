<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0v7p9bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0v7p9bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:trash-simple-thin" /></template>
