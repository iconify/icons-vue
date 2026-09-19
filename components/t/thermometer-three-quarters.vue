<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di8t26b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1792};
const content = `<path class="di8t26b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:thermometer-three-quarters" /></template>
