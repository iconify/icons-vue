<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r335f_bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r335f_bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:text-cursor-input" /></template>
