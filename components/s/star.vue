<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn02wdhyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn02wdhyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:star" /></template>
