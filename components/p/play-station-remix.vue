<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gau3hwb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gau3hwb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:play-station-remix" /></template>
