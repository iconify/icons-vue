<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quacllbqi.css';
import '../../css/c/cily1qbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="quacllbqi"/><path class="cily1qbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-thumbs-up" /></template>
