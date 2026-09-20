<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1uxf8r0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n1uxf8r0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:speech-bubble" /></template>
