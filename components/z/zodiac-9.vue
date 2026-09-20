<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgvooc2bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rgvooc2bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:zodiac-9" /></template>
