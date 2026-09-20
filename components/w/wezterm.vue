<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k80un7zxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k80un7zxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wezterm" /></template>
