<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trzqa8bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trzqa8bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:moodist" /></template>
