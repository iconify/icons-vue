<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri6qttwtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri6qttwtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:volume-1" /></template>
