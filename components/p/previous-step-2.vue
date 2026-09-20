<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nor0fwmgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="nor0fwmgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:previous-step-2" /></template>
