<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epy2y4b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epy2y4b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:picpeak-dark" /></template>
