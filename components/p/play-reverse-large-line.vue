<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncr4eem_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncr4eem_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-reverse-large-line" /></template>
