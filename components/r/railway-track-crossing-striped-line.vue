<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edz9rxbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="edz9rxbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:railway-track-crossing-striped-line" /></template>
