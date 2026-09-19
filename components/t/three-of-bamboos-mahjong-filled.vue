<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgkdl--tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rgkdl--tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:three-of-bamboos-mahjong-filled" /></template>
