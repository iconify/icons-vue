<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqk3295an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oqk3295an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:star-outlined" /></template>
