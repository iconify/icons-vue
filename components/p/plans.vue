<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g00oiob2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g00oiob2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:plans" /></template>
