<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y28-sobij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y28-sobij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:streamlabs" /></template>
