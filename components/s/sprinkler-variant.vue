<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcfi8vkuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcfi8vkuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sprinkler-variant" /></template>
