<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5egc3bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5egc3bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:safe-square-outline" /></template>
