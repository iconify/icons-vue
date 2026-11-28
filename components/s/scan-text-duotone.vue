<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkftjvbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vkftjvbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scan-text-duotone" /></template>
