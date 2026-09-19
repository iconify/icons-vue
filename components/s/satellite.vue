<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqyyk4ovl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nqyyk4ovl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:satellite" /></template>
