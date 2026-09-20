<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcduwehnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wcduwehnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-up-with-plus" /></template>
