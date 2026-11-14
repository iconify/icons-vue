<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib_q_jb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib_q_jb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:receipt-text" /></template>
