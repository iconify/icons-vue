<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyghm0w-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyghm0w-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:pause-circle-outline" /></template>
