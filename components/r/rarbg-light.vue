<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfgerpl9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yfgerpl9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rarbg-light" /></template>
