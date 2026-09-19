<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqe44ubtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yqe44ubtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:web-window-solid" /></template>
