<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofoa5ib1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ofoa5ib1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:vip-filled" /></template>
