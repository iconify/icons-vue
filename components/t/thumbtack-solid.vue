<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i86379gaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i86379gaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:thumbtack-solid" /></template>
