<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv4hsxbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zv4hsxbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:text-compact-duotone" /></template>
