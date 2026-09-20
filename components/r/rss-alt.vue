<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6z0tzbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6z0tzbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:rss-alt" /></template>
