<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crv-b5b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="crv-b5b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:resize-vertical" /></template>
