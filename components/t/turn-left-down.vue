<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrk-82bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrk-82bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:turn-left-down" /></template>
