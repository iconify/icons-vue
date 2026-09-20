<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_bot4blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_bot4blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:medal-fill" /></template>
