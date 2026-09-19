<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2gna1b5o.css';
import '../../css/s/sgyebwbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="t2gna1b5o"/><path class="sgyebwbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:x-circle" /></template>
