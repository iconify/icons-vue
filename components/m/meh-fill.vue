<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spo2f0bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spo2f0bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:meh-fill" /></template>
