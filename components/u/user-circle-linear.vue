<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lcfnqzkei.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/g/gx2slmrgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lcfnqzkei"/><circle class="shu3xdl9q"/><path class="gx2slmrgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-circle-linear" /></template>
