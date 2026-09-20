<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nob8wmdcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nob8wmdcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:monitor-stop-line" /></template>
