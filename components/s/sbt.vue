<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km8wd_zes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="km8wd_zes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sbt" /></template>
