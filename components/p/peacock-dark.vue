<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx18n3bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tx18n3bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peacock-dark" /></template>
