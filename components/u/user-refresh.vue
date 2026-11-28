<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7j255bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7j255bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-refresh" /></template>
