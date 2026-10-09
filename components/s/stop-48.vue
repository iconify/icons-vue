<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd358i0ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hd358i0ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stop-48" /></template>
