<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw1ocebmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="cw1ocebmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:pharmacy-11" /></template>
