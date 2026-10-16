<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-5s4sbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-5s4sbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-octagon-multiple" /></template>
