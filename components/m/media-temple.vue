<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/devq6ibiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="devq6ibiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:media-temple" /></template>
