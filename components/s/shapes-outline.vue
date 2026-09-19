<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up4k305kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up4k305kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:shapes-outline" /></template>
