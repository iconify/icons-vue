<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckrbjib3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckrbjib3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:man" /></template>
