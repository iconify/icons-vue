<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzj3igptw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzj3igptw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:radar-filled" /></template>
