<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbl4_9h2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbl4_9h2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:stretch-horizontal" /></template>
