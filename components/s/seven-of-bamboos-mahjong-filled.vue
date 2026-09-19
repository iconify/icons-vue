<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxlkw4i9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bxlkw4i9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:seven-of-bamboos-mahjong-filled" /></template>
