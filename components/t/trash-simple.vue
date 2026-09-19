<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q54x8h4qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q54x8h4qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:trash-simple" /></template>
