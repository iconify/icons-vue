<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g46yy7bor.css';
import '../../css/w/wdnbtobig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="g46yy7bor"/><path class="wdnbtobig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:strava-statistics" /></template>
