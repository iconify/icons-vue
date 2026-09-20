<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sinukt6es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sinukt6es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:screen-off-outline" /></template>
