<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd1zhtkzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cd1zhtkzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:midi-12" /></template>
