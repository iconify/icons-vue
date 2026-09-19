<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bakgywbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="bakgywbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:sitemap" /></template>
