<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi5tv6bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi5tv6bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:newspaper-plus" /></template>
