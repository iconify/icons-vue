<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v32xzscan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v32xzscan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:toggle-off" /></template>
