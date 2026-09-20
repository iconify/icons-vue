<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scjrk4bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scjrk4bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:qiskit" /></template>
