<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnm2d4hge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnm2d4hge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shield" /></template>
