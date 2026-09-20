<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ietgjjbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ietgjjbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:next" /></template>
