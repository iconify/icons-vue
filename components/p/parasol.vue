<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/filkdbcme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="filkdbcme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:parasol" /></template>
