<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/celtzhb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="celtzhb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:two-of-characters-mahjong" /></template>
