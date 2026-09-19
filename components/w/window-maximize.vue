<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujfs0bcgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="ujfs0bcgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:window-maximize" /></template>
