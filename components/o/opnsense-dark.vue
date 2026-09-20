<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro1qxybqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ro1qxybqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opnsense-dark" /></template>
