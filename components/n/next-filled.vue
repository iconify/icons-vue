<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvat1qb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvat1qb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:next-filled" /></template>
