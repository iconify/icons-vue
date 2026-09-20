<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf9kgebwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf9kgebwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:roman-numeral-4" /></template>
