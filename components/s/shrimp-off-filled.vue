<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6b2rgrbw.css';
import '../../css/l/l5tywcbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6b2rgrbw"/><path class="l5tywcbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shrimp-off-filled" /></template>
