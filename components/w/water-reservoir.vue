<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_8h3-bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_8h3-bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:water-reservoir" /></template>
