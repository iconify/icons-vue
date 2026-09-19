<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4sl_d9vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4sl_d9vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:menu-search" /></template>
