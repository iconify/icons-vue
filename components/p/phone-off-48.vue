<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me0tyib1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="me0tyib1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-off-48" /></template>
