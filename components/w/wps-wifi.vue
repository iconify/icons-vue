<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-s-q8bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-s-q8bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wps-wifi" /></template>
