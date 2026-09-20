<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb280mnli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb280mnli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:play-solid" /></template>
