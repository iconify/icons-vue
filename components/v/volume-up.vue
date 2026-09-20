<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rctcmebyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rctcmebyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:volume-up" /></template>
