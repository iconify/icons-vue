<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8jf6yr1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8jf6yr1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2018-light" /></template>
