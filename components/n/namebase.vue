<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf2sjkbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf2sjkbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:namebase" /></template>
