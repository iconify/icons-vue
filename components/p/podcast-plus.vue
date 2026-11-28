<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc7fnr-0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc7fnr-0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:podcast-plus" /></template>
