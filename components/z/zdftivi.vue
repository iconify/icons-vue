<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rws39ibex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rws39ibex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zdftivi" /></template>
