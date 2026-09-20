<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_h2ic0pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_h2ic0pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tor-browser-light" /></template>
