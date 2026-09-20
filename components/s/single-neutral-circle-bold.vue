<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii1b4wbhw.css';
import '../../css/i/ialwtkkcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1b4wbhw"/><path class="ialwtkkcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:single-neutral-circle-bold" /></template>
