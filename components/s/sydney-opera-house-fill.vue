<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk590ib5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vk590ib5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sydney-opera-house-fill" /></template>
