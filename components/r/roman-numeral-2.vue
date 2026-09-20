<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhthw0hea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhthw0hea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:roman-numeral-2" /></template>
