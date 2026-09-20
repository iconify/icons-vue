<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-__qo4vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p-__qo4vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:surprised-face-with-x-eyes-in-circle" /></template>
