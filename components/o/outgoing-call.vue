<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4vks8bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="n4vks8bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:outgoing-call" /></template>
