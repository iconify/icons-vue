<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2n01eb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2n01eb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rubbish-bin-outline" /></template>
