<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxeo2gbab.css';
import '../../css/q/q8921-8vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxeo2gbab"/><path class="q8921-8vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:meh-line" /></template>
