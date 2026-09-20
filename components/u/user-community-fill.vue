<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkf05g6mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkf05g6mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-community-fill" /></template>
