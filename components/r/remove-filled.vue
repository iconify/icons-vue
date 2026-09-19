<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl_u86lbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pl_u86lbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:remove-filled" /></template>
