<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a01q3idqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a01q3idqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yoink-light" /></template>
