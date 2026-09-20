<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9kgs3l3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9kgs3l3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-vertical" /></template>
