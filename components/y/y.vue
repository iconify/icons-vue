<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on7tvusxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="on7tvusxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:y" /></template>
