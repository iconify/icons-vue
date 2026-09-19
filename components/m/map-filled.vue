<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khtafzbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="khtafzbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:map-filled" /></template>
