<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lem6pvbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lem6pvbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openmediavault" /></template>
