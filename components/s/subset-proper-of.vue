<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u96b__bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u96b__bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:subset-proper-of" /></template>
