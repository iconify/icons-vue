<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxoo1v3ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxoo1v3ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:position" /></template>
