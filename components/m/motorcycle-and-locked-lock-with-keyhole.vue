<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esv2gq_9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="esv2gq_9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-locked-lock-with-keyhole" /></template>
