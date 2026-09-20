<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp238ub8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp238ub8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stairs" /></template>
