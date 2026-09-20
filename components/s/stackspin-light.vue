<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxd62pg6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uxd62pg6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stackspin-light" /></template>
