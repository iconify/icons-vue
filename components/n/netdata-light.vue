<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6vn8uk8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q6vn8uk8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netdata-light" /></template>
