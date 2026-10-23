<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj12ojbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj12ojbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ticket-percent" /></template>
