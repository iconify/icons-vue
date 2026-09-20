<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttx7m2byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttx7m2byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:rss-feed-logo-block" /></template>
