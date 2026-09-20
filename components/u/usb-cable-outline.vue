<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-pmiy5hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n-pmiy5hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:usb-cable-outline" /></template>
