<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6v3-8bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6v3-8bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wand2" /></template>
