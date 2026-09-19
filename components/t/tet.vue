<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4wpl4bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4wpl4bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tet" /></template>
