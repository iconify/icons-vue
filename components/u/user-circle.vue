<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_s7g_bel.css';
import '../../css/r/rz282cqep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_s7g_bel"/><path class="rz282cqep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-circle" /></template>
