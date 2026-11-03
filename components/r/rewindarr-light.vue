<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgwuwtb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgwuwtb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rewindarr-light" /></template>
