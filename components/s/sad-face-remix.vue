<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3ber4bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e3ber4bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sad-face-remix" /></template>
