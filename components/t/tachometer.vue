<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n57qnm33o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n57qnm33o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:tachometer" /></template>
