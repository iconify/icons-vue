<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq1v61m7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq1v61m7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:wrench" /></template>
