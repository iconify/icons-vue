<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7blo6b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7blo6b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:restart-circle-filled" /></template>
