<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg0vg_p2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yg0vg_p2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:smileys-neutral" /></template>
