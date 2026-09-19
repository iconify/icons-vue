<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8-wchbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a8-wchbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:page-facing-up-small" /></template>
