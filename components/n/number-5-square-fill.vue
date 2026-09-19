<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8xe9sbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b8xe9sbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-5-square-fill" /></template>
