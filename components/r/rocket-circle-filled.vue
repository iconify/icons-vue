<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzlibj07q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzlibj07q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rocket-circle-filled" /></template>
