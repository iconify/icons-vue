<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/let3-10tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="let3-10tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teslamate-light" /></template>
