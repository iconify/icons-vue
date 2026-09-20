<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxz-pzbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxz-pzbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-classic" /></template>
