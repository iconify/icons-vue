<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czbd80bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czbd80bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:rename-light" /></template>
