<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzihl_baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzihl_baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pant" /></template>
