<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thsd4275x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thsd4275x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-vertical-thin" /></template>
