<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahkp4zb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ahkp4zb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:train-small" /></template>
