<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se0258yit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se0258yit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:webhook-off" /></template>
