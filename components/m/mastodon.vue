<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nds4ksffh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nds4ksffh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mastodon" /></template>
