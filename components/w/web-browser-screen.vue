<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds3f9kr8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ds3f9kr8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:web-browser-screen" /></template>
