<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_fq1yb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_fq1yb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:toggle-big-left-filled" /></template>
