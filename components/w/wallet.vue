<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjh0vcb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjh0vcb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:wallet" /></template>
