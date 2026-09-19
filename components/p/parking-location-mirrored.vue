<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baozj3bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="baozj3bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:parking-location-mirrored" /></template>
