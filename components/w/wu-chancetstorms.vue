<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnb5mtbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="fnb5mtbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wu-chancetstorms" /></template>
