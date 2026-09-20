<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bss5wybgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bss5wybgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portabase" /></template>
