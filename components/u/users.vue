<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csp1i_y1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csp1i_y1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:users" /></template>
