<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzwz5-bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzwz5-bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:skip-forward" /></template>
