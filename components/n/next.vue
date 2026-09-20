<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3mkfz1sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h3mkfz1sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:next" /></template>
