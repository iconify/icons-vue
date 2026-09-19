<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2csaqbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="v2csaqbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:open-in-browser" /></template>
