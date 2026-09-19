<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqvnn5rbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oqvnn5rbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:u1fae0" /></template>
