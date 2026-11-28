<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku2teloen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku2teloen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:whole-word-solid" /></template>
