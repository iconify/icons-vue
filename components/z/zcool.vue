<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0zn-7b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0zn-7b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zcool" /></template>
