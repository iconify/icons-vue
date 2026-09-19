<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv-v65iws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rv-v65iws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-arrow-dropleft" /></template>
