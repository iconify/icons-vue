<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onj001b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="onj001b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:videocam-sharp" /></template>
