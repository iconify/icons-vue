<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q23-jybty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q23-jybty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:thumb-down-light" /></template>
