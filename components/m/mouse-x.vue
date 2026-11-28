<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjdl12cwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjdl12cwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mouse-x" /></template>
