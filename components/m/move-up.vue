<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otgl_qb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otgl_qb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:move-up" /></template>
