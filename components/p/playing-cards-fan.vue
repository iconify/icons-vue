<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fter9dbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fter9dbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:playing-cards-fan" /></template>
