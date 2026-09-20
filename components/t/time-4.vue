<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_weoss7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_weoss7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:time-4" /></template>
