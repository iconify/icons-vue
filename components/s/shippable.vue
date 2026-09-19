<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc0n45fmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sc0n45fmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:shippable" /></template>
