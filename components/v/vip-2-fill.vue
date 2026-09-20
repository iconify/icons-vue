<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-_0dhbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-_0dhbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-2-fill" /></template>
