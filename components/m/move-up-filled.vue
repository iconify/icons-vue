<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmcuqmblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mmcuqmblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:move-up-filled" /></template>
