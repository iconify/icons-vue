<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbi7kmqhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dbi7kmqhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-magnifying-glass-small-filled" /></template>
