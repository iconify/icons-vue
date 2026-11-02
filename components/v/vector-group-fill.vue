<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj8d-0s5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj8d-0s5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-group-fill" /></template>
