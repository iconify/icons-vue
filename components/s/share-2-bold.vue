<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kujboibdf.css';
import '../../css/t/txm8quc0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kujboibdf"/><path class="txm8quc0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:share-2-bold" /></template>
