<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk-3x8b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk-3x8b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:slice-filled" /></template>
