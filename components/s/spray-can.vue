<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqsrx5gan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqsrx5gan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:spray-can" /></template>
