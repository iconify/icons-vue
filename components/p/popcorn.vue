<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff9-qubkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff9-qubkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:popcorn" /></template>
