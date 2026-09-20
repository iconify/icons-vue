<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u39j05nim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u39j05nim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-key-fill" /></template>
