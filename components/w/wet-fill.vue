<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-hfkdbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h-hfkdbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wet-fill" /></template>
