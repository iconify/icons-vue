<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehw5kccqx.css';
import '../../css/i/irv3-cbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehw5kccqx"/><path class="irv3-cbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:view-list" /></template>
