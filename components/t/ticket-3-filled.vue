<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq423_b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq423_b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ticket-3-filled" /></template>
