<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0np4mbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0np4mbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:target-check" /></template>
