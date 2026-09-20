<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4-y1cbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4-y1cbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:poker-spades-fill" /></template>
