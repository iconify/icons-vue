<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbjntgbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wbjntgbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thunderbird-dark" /></template>
