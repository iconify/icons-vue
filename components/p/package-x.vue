<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyy421bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyy421bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:package-x" /></template>
