<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db9togbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="db9togbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nest-controller" /></template>
