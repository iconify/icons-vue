<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j92q2kbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j92q2kbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:networking-toolbox-dark" /></template>
