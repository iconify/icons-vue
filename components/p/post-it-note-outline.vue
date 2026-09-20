<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkb5c9wkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkb5c9wkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:post-it-note-outline" /></template>
