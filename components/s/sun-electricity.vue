<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbexzvb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbexzvb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sun-electricity" /></template>
