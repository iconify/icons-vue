<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt924p9ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt924p9ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wireless-router" /></template>
