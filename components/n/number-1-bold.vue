<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enctr0ztd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enctr0ztd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-1-bold" /></template>
