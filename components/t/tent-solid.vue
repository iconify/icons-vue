<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc6omccsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc6omccsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tent-solid" /></template>
