<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq_15b37m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq_15b37m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:minus-square-full" /></template>
