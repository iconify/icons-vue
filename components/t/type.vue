<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2pthky2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2pthky2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:type" /></template>
