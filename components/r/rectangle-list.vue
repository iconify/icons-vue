<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubmo3tbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ubmo3tbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:rectangle-list" /></template>
