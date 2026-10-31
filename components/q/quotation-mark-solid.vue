<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv21jdfsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hv21jdfsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:quotation-mark-solid" /></template>
