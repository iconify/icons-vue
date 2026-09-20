<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8qwtlv5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q8qwtlv5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spotify-remix" /></template>
