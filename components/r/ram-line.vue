<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_aa1909b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_aa1909b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ram-line" /></template>
