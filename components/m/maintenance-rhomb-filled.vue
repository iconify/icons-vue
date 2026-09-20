<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4zk5lb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4zk5lb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-rhomb-filled" /></template>
