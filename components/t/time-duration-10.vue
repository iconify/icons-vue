<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty7eelqkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty7eelqkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:time-duration-10" /></template>
