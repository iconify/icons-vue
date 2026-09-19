<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg1nxcods.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg1nxcods"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trending-up-filled" /></template>
