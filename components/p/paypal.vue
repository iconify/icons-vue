<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvtq6p3pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvtq6p3pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:paypal" /></template>
