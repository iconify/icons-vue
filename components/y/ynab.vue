<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5vpad8jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5vpad8jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ynab" /></template>
