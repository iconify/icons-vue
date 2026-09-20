<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1eucru7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="q1eucru7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wand-solid" /></template>
