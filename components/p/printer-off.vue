<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blo0asbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="blo0asbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:printer-off" /></template>
