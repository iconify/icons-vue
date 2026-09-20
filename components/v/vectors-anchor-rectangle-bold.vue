<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtnj1pydm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtnj1pydm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:vectors-anchor-rectangle-bold" /></template>
