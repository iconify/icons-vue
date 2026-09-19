<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk-h9b3te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sk-h9b3te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:umbrella-on-ground" /></template>
