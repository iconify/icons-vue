<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz83p3b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xz83p3b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pause-circle" /></template>
