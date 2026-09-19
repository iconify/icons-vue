<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3hrx-blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="y3hrx-blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:manualshift" /></template>
