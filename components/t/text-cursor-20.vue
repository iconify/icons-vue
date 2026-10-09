<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cambr2b9u.css';
import '../../css/i/iotq56wry.css';
import '../../css/j/jhhngsf8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cambr2b9u"/><path class="iotq56wry"/><path class="jhhngsf8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-cursor-20" /></template>
