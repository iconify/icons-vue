<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvvgatbpq.css';
import '../../css/x/xgwd3dwqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvvgatbpq"/><path class="xgwd3dwqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-bold" /></template>
