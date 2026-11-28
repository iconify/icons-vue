<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rde28zbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rde28zbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:plane-x" /></template>
