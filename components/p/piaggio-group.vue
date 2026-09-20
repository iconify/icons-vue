<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn36lpbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn36lpbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:piaggio-group" /></template>
