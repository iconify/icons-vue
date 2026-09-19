<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a70vaybun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a70vaybun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-9-fill" /></template>
