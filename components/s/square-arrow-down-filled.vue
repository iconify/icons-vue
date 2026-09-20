<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuodqwb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fuodqwb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-down-filled" /></template>
