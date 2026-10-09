<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h048nzb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h048nzb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:menu-20" /></template>
