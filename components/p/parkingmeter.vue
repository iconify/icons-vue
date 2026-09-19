<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_gcnebof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="h_gcnebof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:parkingmeter" /></template>
