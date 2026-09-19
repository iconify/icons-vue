<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nob6eo91n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nob6eo91n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:undo" /></template>
