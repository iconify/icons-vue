<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g43yo4b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g43yo4b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-kiss-solid" /></template>
