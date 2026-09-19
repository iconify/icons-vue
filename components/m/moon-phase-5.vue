<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zezddpp8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zezddpp8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-5" /></template>
