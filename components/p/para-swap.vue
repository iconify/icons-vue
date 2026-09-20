<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx7v_41ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx7v_41ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:para-swap" /></template>
