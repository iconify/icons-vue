<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti3oqpcrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ti3oqpcrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tray" /></template>
