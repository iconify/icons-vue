<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buosklrvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buosklrvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:terminal-solid" /></template>
