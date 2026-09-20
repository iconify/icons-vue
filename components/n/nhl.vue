<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9ml2l_nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9ml2l_nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nhl" /></template>
