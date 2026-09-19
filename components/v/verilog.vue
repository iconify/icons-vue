<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4-_vlatj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4-_vlatj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:verilog" /></template>
