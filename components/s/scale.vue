<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfm4mdbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qfm4mdbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:scale" /></template>
