<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1cnk2djj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b1cnk2djj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-outline" /></template>
