<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig9jrdbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ig9jrdbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:trophy-filled" /></template>
