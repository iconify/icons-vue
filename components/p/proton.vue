<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm6aqd64p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm6aqd64p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:proton" /></template>
