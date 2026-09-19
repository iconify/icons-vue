<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eus48hbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eus48hbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pill-1-24px" /></template>
