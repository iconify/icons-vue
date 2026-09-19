<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkqztmz9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pkqztmz9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:patreon" /></template>
