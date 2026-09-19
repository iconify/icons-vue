<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhb9lzbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhb9lzbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:temperature-low" /></template>
