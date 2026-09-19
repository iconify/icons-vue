<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piij8abfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="piij8abfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mic-circle-sharp" /></template>
