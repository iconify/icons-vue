<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmtjz3qxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmtjz3qxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-four-points" /></template>
