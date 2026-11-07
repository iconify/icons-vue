<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hia_t6bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hia_t6bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signpost-2-bold" /></template>
