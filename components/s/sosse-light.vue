<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fidkc1bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fidkc1bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sosse-light" /></template>
