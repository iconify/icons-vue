<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp0_6tmzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wp0_6tmzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-radio-button-on" /></template>
