<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk0dbfb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk0dbfb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shinto-filled" /></template>
