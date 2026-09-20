<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iumbfubqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iumbfubqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-de-plus" /></template>
