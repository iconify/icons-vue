<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuaqh7tpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuaqh7tpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:table-plus-line" /></template>
