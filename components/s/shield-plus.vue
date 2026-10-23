<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_w_xhb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_w_xhb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shield-plus" /></template>
