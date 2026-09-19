<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpe2vkb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xpe2vkb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:skip-forward" /></template>
