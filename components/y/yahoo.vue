<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdgwk2z5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdgwk2z5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:yahoo" /></template>
