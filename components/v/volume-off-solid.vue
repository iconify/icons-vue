<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u__rqab5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u__rqab5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-off-solid" /></template>
