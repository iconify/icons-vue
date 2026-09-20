<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm1fwac7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm1fwac7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:testin" /></template>
