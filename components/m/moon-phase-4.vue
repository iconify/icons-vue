<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu0ox2bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu0ox2bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-4" /></template>
