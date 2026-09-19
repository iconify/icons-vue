<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaafqclde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yaafqclde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-checkmark-circle-outline" /></template>
