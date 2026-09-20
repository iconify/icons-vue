<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltxg7rblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltxg7rblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-line" /></template>
