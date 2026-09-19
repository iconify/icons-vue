<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0r-zzdsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0r-zzdsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:side-glassdoor-close" /></template>
