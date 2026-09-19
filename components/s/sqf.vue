<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0gdwupyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a0gdwupyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sqf" /></template>
