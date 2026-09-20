<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmolhw4eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmolhw4eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:unfold-more-line" /></template>
