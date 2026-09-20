<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exnrwkbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exnrwkbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:quick-reply" /></template>
