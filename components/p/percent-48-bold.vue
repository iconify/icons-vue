<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgulydb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zgulydb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:percent-48-bold" /></template>
