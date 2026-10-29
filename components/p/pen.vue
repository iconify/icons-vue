<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sna2dnffi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sna2dnffi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pen" /></template>
