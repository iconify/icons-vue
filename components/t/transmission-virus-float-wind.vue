<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-hj12b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-hj12b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:transmission-virus-float-wind" /></template>
