<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi7wnx1bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mi7wnx1bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openpanel-light" /></template>
