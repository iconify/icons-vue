<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihy55zblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ihy55zblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-magnifying-glass-filled" /></template>
