<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpgkfcbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpgkfcbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:waves-vertical" /></template>
