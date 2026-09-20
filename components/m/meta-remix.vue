<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc67oibza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oc67oibza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:meta-remix" /></template>
