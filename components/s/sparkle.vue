<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v832uobfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v832uobfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sparkle" /></template>
