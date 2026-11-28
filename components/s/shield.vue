<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxplbz68r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxplbz68r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shield" /></template>
