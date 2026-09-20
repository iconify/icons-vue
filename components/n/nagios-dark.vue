<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlrgzl5mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nlrgzl5mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nagios-dark" /></template>
