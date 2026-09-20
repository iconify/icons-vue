<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybec0eb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybec0eb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:unread-bold" /></template>
