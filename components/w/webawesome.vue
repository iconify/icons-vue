<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgimotbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgimotbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:webawesome" /></template>
