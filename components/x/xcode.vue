<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx4lb5byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx4lb5byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xcode" /></template>
