<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8_7d2xqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8_7d2xqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pregnancy-pregnant-bold" /></template>
