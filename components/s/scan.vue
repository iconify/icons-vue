<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr5k4eg8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mr5k4eg8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:scan" /></template>
