<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acivrw2rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acivrw2rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-round" /></template>
