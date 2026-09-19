<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pknoky-nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="pknoky-nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tachometer-alt" /></template>
