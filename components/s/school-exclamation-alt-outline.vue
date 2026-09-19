<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tux0n1bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tux0n1bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-exclamation-alt-outline" /></template>
