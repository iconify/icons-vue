<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5ml-gbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l5ml-gbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netonnet-dark" /></template>
