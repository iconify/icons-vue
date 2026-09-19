<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymougub6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ymougub6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-2-circle-fill" /></template>
