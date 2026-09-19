<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk1lm37nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hk1lm37nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:qq-filled" /></template>
