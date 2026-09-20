<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi6dgzbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi6dgzbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:volume" /></template>
