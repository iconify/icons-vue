<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpm4zwb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jpm4zwb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:remove-circle" /></template>
