<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvy1gibog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mvy1gibog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:view-list-small" /></template>
