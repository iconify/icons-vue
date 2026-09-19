<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0wdczblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0wdczblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-vertical-duotone" /></template>
