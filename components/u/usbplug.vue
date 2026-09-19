<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csg4-9uxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="csg4-9uxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:usbplug" /></template>
