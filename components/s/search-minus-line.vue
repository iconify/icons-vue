<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkuguacuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkuguacuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:search-minus-line" /></template>
