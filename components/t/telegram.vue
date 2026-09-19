<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb907bc8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hb907bc8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:telegram" /></template>
