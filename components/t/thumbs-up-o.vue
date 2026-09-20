<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw644_pji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vw644_pji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:thumbs-up-o" /></template>
