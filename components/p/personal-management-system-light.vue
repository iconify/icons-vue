<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u37d7hbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u37d7hbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:personal-management-system-light" /></template>
