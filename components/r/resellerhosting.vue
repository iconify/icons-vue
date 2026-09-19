<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe_1rzbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fe_1rzbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:resellerhosting" /></template>
