<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juilb0dgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="juilb0dgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:qiskit" /></template>
