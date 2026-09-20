<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of_484bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="of_484bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smoke-detector-remix" /></template>
