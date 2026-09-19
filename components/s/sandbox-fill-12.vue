<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua9bmhbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ua9bmhbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sandbox-fill-12" /></template>
