<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp4d9t4hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xp4d9t4hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:size-text-filled" /></template>
