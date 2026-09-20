<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi76c70-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi76c70-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-mini-line" /></template>
