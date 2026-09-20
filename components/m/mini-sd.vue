<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st5_1o_9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st5_1o_9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mini-sd" /></template>
