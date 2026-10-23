<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oofs6vwkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oofs6vwkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:popsicle" /></template>
