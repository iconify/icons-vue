<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvo5b-0za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nvo5b-0za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:navigation-20" /></template>
