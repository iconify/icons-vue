<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njt32-bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="njt32-bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:soft-ice-cream" /></template>
