<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbu6h1ink.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dbu6h1ink"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:open-book" /></template>
