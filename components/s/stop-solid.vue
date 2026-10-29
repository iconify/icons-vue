<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig7r6rpsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig7r6rpsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stop-solid" /></template>
