<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_wv7rbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_wv7rbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-square-filled" /></template>
