<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yexni8b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yexni8b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:row-plus-filled" /></template>
