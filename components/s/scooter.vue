<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul832ibzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ul832ibzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:scooter" /></template>
