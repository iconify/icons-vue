<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7hr3-2pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h7hr3-2pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:star-16-solid" /></template>
