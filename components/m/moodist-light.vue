<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxa3dwbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxa3dwbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:moodist-light" /></template>
