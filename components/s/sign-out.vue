<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uodm3s_en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uodm3s_en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:sign-out" /></template>
