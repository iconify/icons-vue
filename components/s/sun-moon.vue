<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceu5rcmux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceu5rcmux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sun-moon" /></template>
