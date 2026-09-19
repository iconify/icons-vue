<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noljisb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="noljisb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:menu-stroke-12" /></template>
