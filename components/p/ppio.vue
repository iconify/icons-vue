<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5qx-mtxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p5qx-mtxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ppio" /></template>
