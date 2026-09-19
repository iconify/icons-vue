<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnjcyuboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnjcyuboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:message" /></template>
