<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p11hu73fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p11hu73fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:termius" /></template>
