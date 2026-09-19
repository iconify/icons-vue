<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me6dbccby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="me6dbccby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:tv-retro" /></template>
