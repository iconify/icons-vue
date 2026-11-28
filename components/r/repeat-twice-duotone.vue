<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nds8wgdzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nds8wgdzq primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:repeat-twice-duotone" /></template>
