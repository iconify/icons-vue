<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wib0hymia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wib0hymia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:newbalance" /></template>
