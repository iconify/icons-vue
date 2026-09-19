<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc82i_bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vc82i_bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:minimize-fill-16" /></template>
