<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tquf41b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tquf41b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:minimize-fill" /></template>
