<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6ntifonz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u6ntifonz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-10-remix" /></template>
