<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgzzj0u0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgzzj0u0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:thumbs-up" /></template>
