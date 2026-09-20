<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzh6wybpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tzh6wybpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-1-solid" /></template>
