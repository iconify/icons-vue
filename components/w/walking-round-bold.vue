<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhgzc94rg.css';
import '../../css/n/nr1pzgbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhgzc94rg"/><path clip-rule="evenodd" class="nr1pzgbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:walking-round-bold" /></template>
