<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8ziwgk5l.css';
import '../../css/e/er7ag9bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g8ziwgk5l"/><path class="er7ag9bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:workbrew" /></template>
