<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txws23bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txws23bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:trending-down" /></template>
