<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si0cvqbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":408};
const content = `<path class="si0cvqbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:phone-ring" /></template>
