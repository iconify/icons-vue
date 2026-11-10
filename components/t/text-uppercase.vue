<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mft06ikyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mft06ikyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-uppercase" /></template>
