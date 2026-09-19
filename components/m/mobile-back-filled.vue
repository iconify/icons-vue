<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp6h30bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp6h30bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mobile-back-filled" /></template>
