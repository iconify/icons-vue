<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj86m0dbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj86m0dbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:web-grid-alt" /></template>
