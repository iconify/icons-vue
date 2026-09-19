<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-4g-9byg.css';
import '../../css/a/a2og3c3yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-4g-9byg"/><path class="a2og3c3yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-star" /></template>
