<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2r6-ab1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="y2r6-ab1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:mastodon" /></template>
