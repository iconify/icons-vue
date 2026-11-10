<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-pm6rssb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-pm6rssb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-flame" /></template>
