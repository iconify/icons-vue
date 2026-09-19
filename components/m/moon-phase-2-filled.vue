<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt117bbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt117bbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-2-filled" /></template>
