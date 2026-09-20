<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1r3rgtye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r1r3rgtye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:triangle-filled" /></template>
