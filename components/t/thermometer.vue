<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae0_nebny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ae0_nebny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:thermometer" /></template>
