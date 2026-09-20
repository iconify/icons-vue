<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9j5775fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x9j5775fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rain-cloud-remix" /></template>
