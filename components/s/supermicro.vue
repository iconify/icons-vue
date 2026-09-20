<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjly1mbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjly1mbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:supermicro" /></template>
