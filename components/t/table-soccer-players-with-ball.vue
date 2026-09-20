<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd9p4freu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pd9p4freu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:table-soccer-players-with-ball" /></template>
