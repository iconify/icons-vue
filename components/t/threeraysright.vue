<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmoi7hkoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wmoi7hkoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:threeraysright" /></template>
