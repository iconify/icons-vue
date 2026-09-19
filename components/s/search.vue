<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di38cgbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di38cgbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:search" /></template>
