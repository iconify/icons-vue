<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhmr2ua0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhmr2ua0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ship-steering-wheel" /></template>
