<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td_b_qzjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td_b_qzjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:padlock" /></template>
