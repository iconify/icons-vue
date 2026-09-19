<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svy3we4zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svy3we4zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:move-h" /></template>
