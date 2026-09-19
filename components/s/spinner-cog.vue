<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unkg9gb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unkg9gb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:spinner-cog" /></template>
