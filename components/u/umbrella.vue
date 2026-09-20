<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnsu8pbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnsu8pbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:umbrella" /></template>
