<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihbbv98gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihbbv98gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rybbit-dark" /></template>
