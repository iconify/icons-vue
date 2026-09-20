<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyv38rbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyv38rbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vine" /></template>
