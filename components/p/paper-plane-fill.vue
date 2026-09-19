<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuu7943dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuu7943dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:paper-plane-fill" /></template>
