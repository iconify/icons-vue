<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttbxzejoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttbxzejoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-circle-bold" /></template>
