<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzcm4hlba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hzcm4hlba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:target-dark" /></template>
