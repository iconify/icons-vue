<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm0eplbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm0eplbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sunyou" /></template>
