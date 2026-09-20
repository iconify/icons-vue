<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbt4z81as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbt4z81as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:reply-fill" /></template>
