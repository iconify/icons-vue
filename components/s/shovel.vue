<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iua0cyb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iua0cyb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:shovel" /></template>
