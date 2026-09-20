<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bocc0t2az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bocc0t2az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:scheme" /></template>
