<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe-0n0bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe-0n0bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stamp-check" /></template>
