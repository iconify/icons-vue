<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_2wtsbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f_2wtsbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mosquito2x-outline" /></template>
