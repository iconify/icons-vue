<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia6yr0bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ia6yr0bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openttd-dark" /></template>
