<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rry_6hbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rry_6hbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vinted" /></template>
