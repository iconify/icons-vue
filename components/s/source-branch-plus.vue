<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra2b73bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra2b73bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:source-branch-plus" /></template>
