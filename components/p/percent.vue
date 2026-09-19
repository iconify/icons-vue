<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v20uhpbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="v20uhpbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:percent" /></template>
