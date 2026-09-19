<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh8iyzb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh8iyzb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:paper-clip-solid" /></template>
