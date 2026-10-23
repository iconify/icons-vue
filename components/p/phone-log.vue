<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji-jtbsbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji-jtbsbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:phone-log" /></template>
