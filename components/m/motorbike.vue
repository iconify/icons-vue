<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icze2zluo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icze2zluo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:motorbike" /></template>
