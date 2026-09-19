<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roy_pgb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="roy_pgb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:orchid-mahjong" /></template>
