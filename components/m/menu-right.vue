<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpw970bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpw970bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu-right" /></template>
