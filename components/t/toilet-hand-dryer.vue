<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsm3ucbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsm3ucbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:toilet-hand-dryer" /></template>
