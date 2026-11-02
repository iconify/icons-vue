<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayln2ubqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayln2ubqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scissors-fill" /></template>
