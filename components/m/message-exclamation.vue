<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p56h_bbeb.css';
import '../../css/p/p6khhubye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p56h_bbeb"/><path class="p6khhubye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-exclamation" /></template>
