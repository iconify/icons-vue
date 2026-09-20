<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn29kgakn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn29kgakn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qiskit" /></template>
