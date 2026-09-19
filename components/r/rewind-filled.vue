<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc93vrbkc.css';
import '../../css/z/zho_0_ruy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc93vrbkc"/><path class="zho_0_ruy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rewind-filled" /></template>
