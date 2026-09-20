<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoe1u27hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoe1u27hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:source-commit-end" /></template>
