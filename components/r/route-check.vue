<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2guufm2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2guufm2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:route-check" /></template>
