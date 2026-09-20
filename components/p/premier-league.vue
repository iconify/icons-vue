<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pym99p-_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pym99p-_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:premier-league" /></template>
