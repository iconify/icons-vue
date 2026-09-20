<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f38u625eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f38u625eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:satellite-filled" /></template>
