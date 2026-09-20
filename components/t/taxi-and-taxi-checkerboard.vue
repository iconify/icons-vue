<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm515tbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qm515tbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:taxi-and-taxi-checkerboard" /></template>
