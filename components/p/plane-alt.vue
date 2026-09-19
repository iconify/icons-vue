<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv996kwky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv996kwky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plane-alt" /></template>
