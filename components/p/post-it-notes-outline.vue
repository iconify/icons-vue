<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsj37ibve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsj37ibve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:post-it-notes-outline" /></template>
