<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui42cb9px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui42cb9px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ziggo" /></template>
