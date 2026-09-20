<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vufb63byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vufb63byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wifi-horizontal-remix" /></template>
