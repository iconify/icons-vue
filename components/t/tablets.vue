<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcx_ksbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcx_ksbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tablets" /></template>
