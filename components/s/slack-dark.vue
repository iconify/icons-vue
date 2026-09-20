<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce61z2uyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ce61z2uyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slack-dark" /></template>
