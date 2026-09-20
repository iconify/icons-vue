<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unuff3bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unuff3bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:weather-snow" /></template>
