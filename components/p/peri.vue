<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz1vnob6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz1vnob6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:peri" /></template>
