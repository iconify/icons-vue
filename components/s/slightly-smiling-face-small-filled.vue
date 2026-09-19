<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chmzr6tus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="chmzr6tus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:slightly-smiling-face-small-filled" /></template>
