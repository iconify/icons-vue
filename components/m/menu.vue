<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w79-7zbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w79-7zbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:menu" /></template>
