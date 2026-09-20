<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcsywwuje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rcsywwuje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sound-loud-filled" /></template>
