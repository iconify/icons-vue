<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u39w7bpfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u39w7bpfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tv-minimal" /></template>
