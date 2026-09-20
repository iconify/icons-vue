<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eog45o2id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eog45o2id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-services-light" /></template>
