<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lljgh4k1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lljgh4k1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2018-dark" /></template>
