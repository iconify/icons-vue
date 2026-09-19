<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rum1esb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rum1esb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-arrow-round-up" /></template>
