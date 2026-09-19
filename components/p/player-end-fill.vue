<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me8lomb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="me8lomb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-end-fill" /></template>
