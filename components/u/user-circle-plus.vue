<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyg5edm9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyg5edm9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-circle-plus" /></template>
