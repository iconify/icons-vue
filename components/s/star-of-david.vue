<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcnu4fbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mcnu4fbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:star-of-david" /></template>
