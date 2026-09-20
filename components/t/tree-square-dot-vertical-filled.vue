<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1fv2s1fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1fv2s1fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tree-square-dot-vertical-filled" /></template>
