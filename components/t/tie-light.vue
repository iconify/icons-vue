<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxlvwzb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxlvwzb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:tie-light" /></template>
