<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbcw621xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cbcw621xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-dark" /></template>
