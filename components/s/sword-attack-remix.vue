<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnxmfkbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnxmfkbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sword-attack-remix" /></template>
