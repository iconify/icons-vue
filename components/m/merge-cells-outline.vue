<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kflreebxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kflreebxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:merge-cells-outline" /></template>
