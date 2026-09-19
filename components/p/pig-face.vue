<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me6yobbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="me6yobbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:pig-face" /></template>
