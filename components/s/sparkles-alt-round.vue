<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmck85i-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmck85i-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sparkles-alt-round" /></template>
