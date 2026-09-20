<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr6936bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mr6936bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tarot" /></template>
