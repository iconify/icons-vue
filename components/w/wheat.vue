<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7fh-abpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7fh-abpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wheat" /></template>
