<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp7cuw3ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp7cuw3ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:users-plus" /></template>
