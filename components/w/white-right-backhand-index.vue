<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhe7dvyvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vhe7dvyvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:white-right-backhand-index" /></template>
