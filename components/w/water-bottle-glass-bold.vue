<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkuydybda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkuydybda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:water-bottle-glass-bold" /></template>
