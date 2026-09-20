<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x686wac0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x686wac0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shuffle-solid" /></template>
