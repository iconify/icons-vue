<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itsdl0bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="itsdl0bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:unlink-horizontal" /></template>
