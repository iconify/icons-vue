<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mll4yq1pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mll4yq1pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:umbrella-line" /></template>
