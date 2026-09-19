<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy5-_ebch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="sy5-_ebch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:removetags" /></template>
