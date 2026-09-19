<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk0xwtbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kk0xwtbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:thunderstorm-outline" /></template>
