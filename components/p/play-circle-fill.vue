<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pttofhins.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pttofhins"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:play-circle-fill" /></template>
