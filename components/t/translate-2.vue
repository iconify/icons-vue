<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyy1-b-7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyy1-b-7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:translate-2" /></template>
