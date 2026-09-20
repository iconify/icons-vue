<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aav1k0baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aav1k0baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:play-hexagon-solid" /></template>
