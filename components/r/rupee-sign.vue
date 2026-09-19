<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz1m2xbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dz1m2xbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:rupee-sign" /></template>
