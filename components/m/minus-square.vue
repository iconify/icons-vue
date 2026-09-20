<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwaaf0-ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwaaf0-ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:minus-square" /></template>
