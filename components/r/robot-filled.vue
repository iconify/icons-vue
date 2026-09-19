<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv-ung4uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wv-ung4uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:robot-filled" /></template>
