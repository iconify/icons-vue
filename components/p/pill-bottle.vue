<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhnc_uboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhnc_uboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pill-bottle" /></template>
