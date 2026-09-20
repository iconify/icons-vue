<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5hg73b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="v5hg73b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-10" /></template>
