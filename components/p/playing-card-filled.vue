<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym02nvber.css';
import '../../css/w/wb_c6o2qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym02nvber"/><path clip-rule="evenodd" class="wb_c6o2qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:playing-card-filled" /></template>
