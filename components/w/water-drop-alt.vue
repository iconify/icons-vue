<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bntn4zffv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bntn4zffv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:water-drop-alt" /></template>
