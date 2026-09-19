<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmy-uob3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmy-uob3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:temperature" /></template>
