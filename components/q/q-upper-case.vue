<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f12wigmwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":795,"height":813};
const content = `<path class="f12wigmwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:q-upper-case" /></template>
