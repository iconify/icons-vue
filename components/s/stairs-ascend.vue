<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7jml-bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f7jml-bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:stairs-ascend" /></template>
