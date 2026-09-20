<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whp7a6bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="whp7a6bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tipi-campsite-with-shekel" /></template>
