<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjrzm9bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sjrzm9bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:worm" /></template>
