<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og6harflv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="og6harflv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-alp-light" /></template>
