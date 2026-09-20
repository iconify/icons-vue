<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrcz0db9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="nrcz0db9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:prison-11" /></template>
