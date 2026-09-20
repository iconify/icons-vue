<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9aa3xh8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9aa3xh8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-2-linear" /></template>
