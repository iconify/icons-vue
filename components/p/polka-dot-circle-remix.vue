<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfatfab1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gfatfab1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:polka-dot-circle-remix" /></template>
