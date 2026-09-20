<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vktmc_wue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vktmc_wue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:trending-down" /></template>
