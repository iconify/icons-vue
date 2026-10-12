<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp3rf-aea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vp3rf-aea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:medical-cross-48-bold" /></template>
