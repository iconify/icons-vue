<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8tlm64ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1472};
const content = `<path class="b8tlm64ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:sleep" /></template>
