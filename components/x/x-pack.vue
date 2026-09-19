<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7io4dvsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d7io4dvsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:x-pack" /></template>
