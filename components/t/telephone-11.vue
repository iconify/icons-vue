<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rco92cb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="rco92cb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:telephone-11" /></template>
