<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3d10iwra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3d10iwra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:number-nine-bold" /></template>
