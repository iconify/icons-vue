<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clkb5-fug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clkb5-fug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:transmission-virus-human-infected" /></template>
