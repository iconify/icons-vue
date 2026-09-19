<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl470_b0c.css';
import '../../css/x/xgglfabho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl470_b0c"/><path class="xgglfabho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:phone-ring" /></template>
