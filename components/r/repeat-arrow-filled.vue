<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n22-7p18b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n22-7p18b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:repeat-arrow-filled" /></template>
