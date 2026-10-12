<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym02nvber.css';
import '../../css/u/unrc__8ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym02nvber"/><path clip-rule="evenodd" class="unrc__8ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:playing-card-filled" /></template>
