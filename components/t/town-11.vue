<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uthf9xbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="uthf9xbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:town-11" /></template>
