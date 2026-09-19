<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs0_786be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xs0_786be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:rabbit-face" /></template>
