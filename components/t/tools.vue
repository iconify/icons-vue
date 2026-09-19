<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlei2-bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jlei2-bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tools" /></template>
