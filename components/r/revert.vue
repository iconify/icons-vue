<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duiy32tko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="duiy32tko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:revert" /></template>
