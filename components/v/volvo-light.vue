<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fde7o7i7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fde7o7i7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:volvo-light" /></template>
