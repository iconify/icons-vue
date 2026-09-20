<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo74jw5my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo74jw5my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:spinner" /></template>
