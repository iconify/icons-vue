<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqm0ehbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqm0ehbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ticket-alt-1-line" /></template>
