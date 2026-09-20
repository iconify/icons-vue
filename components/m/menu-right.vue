<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8v4adbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n8v4adbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:menu-right" /></template>
