<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u29dkabod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u29dkabod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-solid" /></template>
