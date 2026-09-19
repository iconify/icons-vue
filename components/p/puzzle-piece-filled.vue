<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_h_9xbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_h_9xbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:puzzle-piece-filled" /></template>
